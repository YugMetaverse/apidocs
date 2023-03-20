[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MediaPlayer

# Class: MediaPlayer

[ue/ue](../modules/ue_ue.md).MediaPlayer

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MediaPlayer`**

## Table of contents

### Constructors

- [constructor](ue_ue.MediaPlayer.md#constructor)

### Properties

- [AffectedByPIEHandling](ue_ue.MediaPlayer.md#affectedbypiehandling)
- [CacheAhead](ue_ue.MediaPlayer.md#cacheahead)
- [CacheBehind](ue_ue.MediaPlayer.md#cachebehind)
- [CacheBehindGame](ue_ue.MediaPlayer.md#cachebehindgame)
- [HorizontalFieldOfView](ue_ue.MediaPlayer.md#horizontalfieldofview)
- [Loop](ue_ue.MediaPlayer.md#loop)
- [NativeAudioOut](ue_ue.MediaPlayer.md#nativeaudioout)
- [OnEndReached](ue_ue.MediaPlayer.md#onendreached)
- [OnMediaClosed](ue_ue.MediaPlayer.md#onmediaclosed)
- [OnMediaOpenFailed](ue_ue.MediaPlayer.md#onmediaopenfailed)
- [OnMediaOpened](ue_ue.MediaPlayer.md#onmediaopened)
- [OnPlaybackResumed](ue_ue.MediaPlayer.md#onplaybackresumed)
- [OnPlaybackSuspended](ue_ue.MediaPlayer.md#onplaybacksuspended)
- [OnSeekCompleted](ue_ue.MediaPlayer.md#onseekcompleted)
- [OnTracksChanged](ue_ue.MediaPlayer.md#ontrackschanged)
- [PlayOnOpen](ue_ue.MediaPlayer.md#playonopen)
- [PlayerGuid](ue_ue.MediaPlayer.md#playerguid)
- [Playlist](ue_ue.MediaPlayer.md#playlist)
- [PlaylistIndex](ue_ue.MediaPlayer.md#playlistindex)
- [Shuffle](ue_ue.MediaPlayer.md#shuffle)
- [TimeDelay](ue_ue.MediaPlayer.md#timedelay)
- [VerticalFieldOfView](ue_ue.MediaPlayer.md#verticalfieldofview)
- [ViewRotation](ue_ue.MediaPlayer.md#viewrotation)
- [\_\_tid\_MediaPlayer\_\_](ue_ue.MediaPlayer.md#__tid_mediaplayer__)
- [\_\_tid\_Object\_\_](ue_ue.MediaPlayer.md#__tid_object__)

### Methods

- [CanPause](ue_ue.MediaPlayer.md#canpause)
- [CanPlaySource](ue_ue.MediaPlayer.md#canplaysource)
- [CanPlayUrl](ue_ue.MediaPlayer.md#canplayurl)
- [Close](ue_ue.MediaPlayer.md#close)
- [CreateDefaultSubobject](ue_ue.MediaPlayer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MediaPlayer.md#executeubergraph)
- [GetAudioTrackChannels](ue_ue.MediaPlayer.md#getaudiotrackchannels)
- [GetAudioTrackSampleRate](ue_ue.MediaPlayer.md#getaudiotracksamplerate)
- [GetAudioTrackType](ue_ue.MediaPlayer.md#getaudiotracktype)
- [GetClass](ue_ue.MediaPlayer.md#getclass)
- [GetDesiredPlayerName](ue_ue.MediaPlayer.md#getdesiredplayername)
- [GetDuration](ue_ue.MediaPlayer.md#getduration)
- [GetHorizontalFieldOfView](ue_ue.MediaPlayer.md#gethorizontalfieldofview)
- [GetLastAudioSampleProcessedTime](ue_ue.MediaPlayer.md#getlastaudiosampleprocessedtime)
- [GetLastVideoSampleProcessedTime](ue_ue.MediaPlayer.md#getlastvideosampleprocessedtime)
- [GetMediaName](ue_ue.MediaPlayer.md#getmedianame)
- [GetName](ue_ue.MediaPlayer.md#getname)
- [GetNumTrackFormats](ue_ue.MediaPlayer.md#getnumtrackformats)
- [GetNumTracks](ue_ue.MediaPlayer.md#getnumtracks)
- [GetOuter](ue_ue.MediaPlayer.md#getouter)
- [GetPlayerName](ue_ue.MediaPlayer.md#getplayername)
- [GetPlaylist](ue_ue.MediaPlayer.md#getplaylist)
- [GetPlaylistIndex](ue_ue.MediaPlayer.md#getplaylistindex)
- [GetRate](ue_ue.MediaPlayer.md#getrate)
- [GetSelectedTrack](ue_ue.MediaPlayer.md#getselectedtrack)
- [GetSupportedRates](ue_ue.MediaPlayer.md#getsupportedrates)
- [GetTime](ue_ue.MediaPlayer.md#gettime)
- [GetTimeDelay](ue_ue.MediaPlayer.md#gettimedelay)
- [GetTrackDisplayName](ue_ue.MediaPlayer.md#gettrackdisplayname)
- [GetTrackFormat](ue_ue.MediaPlayer.md#gettrackformat)
- [GetTrackLanguage](ue_ue.MediaPlayer.md#gettracklanguage)
- [GetUrl](ue_ue.MediaPlayer.md#geturl)
- [GetVerticalFieldOfView](ue_ue.MediaPlayer.md#getverticalfieldofview)
- [GetVideoTrackAspectRatio](ue_ue.MediaPlayer.md#getvideotrackaspectratio)
- [GetVideoTrackDimensions](ue_ue.MediaPlayer.md#getvideotrackdimensions)
- [GetVideoTrackFrameRate](ue_ue.MediaPlayer.md#getvideotrackframerate)
- [GetVideoTrackFrameRates](ue_ue.MediaPlayer.md#getvideotrackframerates)
- [GetVideoTrackType](ue_ue.MediaPlayer.md#getvideotracktype)
- [GetViewRotation](ue_ue.MediaPlayer.md#getviewrotation)
- [GetWorld](ue_ue.MediaPlayer.md#getworld)
- [HasError](ue_ue.MediaPlayer.md#haserror)
- [IsBuffering](ue_ue.MediaPlayer.md#isbuffering)
- [IsClosed](ue_ue.MediaPlayer.md#isclosed)
- [IsConnecting](ue_ue.MediaPlayer.md#isconnecting)
- [IsLooping](ue_ue.MediaPlayer.md#islooping)
- [IsPaused](ue_ue.MediaPlayer.md#ispaused)
- [IsPlaying](ue_ue.MediaPlayer.md#isplaying)
- [IsPreparing](ue_ue.MediaPlayer.md#ispreparing)
- [IsReady](ue_ue.MediaPlayer.md#isready)
- [Next](ue_ue.MediaPlayer.md#next)
- [OpenFile](ue_ue.MediaPlayer.md#openfile)
- [OpenPlaylist](ue_ue.MediaPlayer.md#openplaylist)
- [OpenPlaylistIndex](ue_ue.MediaPlayer.md#openplaylistindex)
- [OpenSource](ue_ue.MediaPlayer.md#opensource)
- [OpenSourceLatent](ue_ue.MediaPlayer.md#opensourcelatent)
- [OpenSourceWithOptions](ue_ue.MediaPlayer.md#opensourcewithoptions)
- [OpenUrl](ue_ue.MediaPlayer.md#openurl)
- [Pause](ue_ue.MediaPlayer.md#pause)
- [Play](ue_ue.MediaPlayer.md#play)
- [Previous](ue_ue.MediaPlayer.md#previous)
- [Reopen](ue_ue.MediaPlayer.md#reopen)
- [Rewind](ue_ue.MediaPlayer.md#rewind)
- [Seek](ue_ue.MediaPlayer.md#seek)
- [SelectTrack](ue_ue.MediaPlayer.md#selecttrack)
- [SetBlockOnTime](ue_ue.MediaPlayer.md#setblockontime)
- [SetDesiredPlayerName](ue_ue.MediaPlayer.md#setdesiredplayername)
- [SetLooping](ue_ue.MediaPlayer.md#setlooping)
- [SetMediaOptions](ue_ue.MediaPlayer.md#setmediaoptions)
- [SetNativeVolume](ue_ue.MediaPlayer.md#setnativevolume)
- [SetRate](ue_ue.MediaPlayer.md#setrate)
- [SetTimeDelay](ue_ue.MediaPlayer.md#settimedelay)
- [SetTrackFormat](ue_ue.MediaPlayer.md#settrackformat)
- [SetVideoTrackFrameRate](ue_ue.MediaPlayer.md#setvideotrackframerate)
- [SetViewField](ue_ue.MediaPlayer.md#setviewfield)
- [SetViewRotation](ue_ue.MediaPlayer.md#setviewrotation)
- [SupportsRate](ue_ue.MediaPlayer.md#supportsrate)
- [SupportsScrubbing](ue_ue.MediaPlayer.md#supportsscrubbing)
- [SupportsSeeking](ue_ue.MediaPlayer.md#supportsseeking)
- [Find](ue_ue.MediaPlayer.md#find)
- [Load](ue_ue.MediaPlayer.md#load)
- [StaticClass](ue_ue.MediaPlayer.md#staticclass)

## Constructors

### constructor

• **new MediaPlayer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:50178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50178)

## Properties

### AffectedByPIEHandling

• **AffectedByPIEHandling**: `boolean`

#### Defined in

[ue/ue.d.ts:50201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50201)

___

### CacheAhead

• **CacheAhead**: [`Timespan`](ue_ue.Timespan.md)

#### Defined in

[ue/ue.d.ts:50187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50187)

___

### CacheBehind

• **CacheBehind**: [`Timespan`](ue_ue.Timespan.md)

#### Defined in

[ue/ue.d.ts:50188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50188)

___

### CacheBehindGame

• **CacheBehindGame**: [`Timespan`](ue_ue.Timespan.md)

#### Defined in

[ue/ue.d.ts:50189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50189)

___

### HorizontalFieldOfView

• **HorizontalFieldOfView**: `number`

#### Defined in

[ue/ue.d.ts:50197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50197)

___

### Loop

• **Loop**: `boolean`

#### Defined in

[ue/ue.d.ts:50193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50193)

___

### NativeAudioOut

• **NativeAudioOut**: `boolean`

#### Defined in

[ue/ue.d.ts:50190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50190)

___

### OnEndReached

• **OnEndReached**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:50179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50179)

___

### OnMediaClosed

• **OnMediaClosed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:50180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50180)

___

### OnMediaOpenFailed

• **OnMediaOpenFailed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FailedUrl`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:50182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50182)

___

### OnMediaOpened

• **OnMediaOpened**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OpenedUrl`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:50181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50181)

___

### OnPlaybackResumed

• **OnPlaybackResumed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:50183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50183)

___

### OnPlaybackSuspended

• **OnPlaybackSuspended**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:50184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50184)

___

### OnSeekCompleted

• **OnSeekCompleted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:50185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50185)

___

### OnTracksChanged

• **OnTracksChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:50186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50186)

___

### PlayOnOpen

• **PlayOnOpen**: `boolean`

#### Defined in

[ue/ue.d.ts:50191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50191)

___

### PlayerGuid

• **PlayerGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:50200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50200)

___

### Playlist

• **Playlist**: [`MediaPlaylist`](ue_ue.MediaPlaylist.md)

#### Defined in

[ue/ue.d.ts:50194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50194)

___

### PlaylistIndex

• **PlaylistIndex**: `number`

#### Defined in

[ue/ue.d.ts:50195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50195)

___

### Shuffle

• **Shuffle**: `boolean`

#### Defined in

[ue/ue.d.ts:50192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50192)

___

### TimeDelay

• **TimeDelay**: [`Timespan`](ue_ue.Timespan.md)

#### Defined in

[ue/ue.d.ts:50196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50196)

___

### VerticalFieldOfView

• **VerticalFieldOfView**: `number`

#### Defined in

[ue/ue.d.ts:50198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50198)

___

### ViewRotation

• **ViewRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:50199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50199)

___

### \_\_tid\_MediaPlayer\_\_

• **\_\_tid\_MediaPlayer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:50278](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50278)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

## Methods

### CanPause

▸ **CanPause**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50202)

___

### CanPlaySource

▸ **CanPlaySource**(`MediaSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50203)

___

### CanPlayUrl

▸ **CanPlayUrl**(`Url`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Url` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50204)

___

### Close

▸ **Close**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:50205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50205)

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

### GetAudioTrackChannels

▸ **GetAudioTrackChannels**(`TrackIndex`, `FormatIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50206)

___

### GetAudioTrackSampleRate

▸ **GetAudioTrackSampleRate**(`TrackIndex`, `FormatIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50207)

___

### GetAudioTrackType

▸ **GetAudioTrackType**(`TrackIndex`, `FormatIndex`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:50208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50208)

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

### GetDesiredPlayerName

▸ **GetDesiredPlayerName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:50209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50209)

___

### GetDuration

▸ **GetDuration**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

#### Defined in

[ue/ue.d.ts:50210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50210)

___

### GetHorizontalFieldOfView

▸ **GetHorizontalFieldOfView**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50211)

___

### GetLastAudioSampleProcessedTime

▸ **GetLastAudioSampleProcessedTime**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

#### Defined in

[ue/ue.d.ts:50212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50212)

___

### GetLastVideoSampleProcessedTime

▸ **GetLastVideoSampleProcessedTime**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

#### Defined in

[ue/ue.d.ts:50213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50213)

___

### GetMediaName

▸ **GetMediaName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:50214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50214)

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

### GetNumTrackFormats

▸ **GetNumTrackFormats**(`TrackType`, `TrackIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |
| `TrackIndex` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50215)

___

### GetNumTracks

▸ **GetNumTracks**(`TrackType`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50216)

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

### GetPlayerName

▸ **GetPlayerName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:50217](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50217)

___

### GetPlaylist

▸ **GetPlaylist**(): [`MediaPlaylist`](ue_ue.MediaPlaylist.md)

#### Returns

[`MediaPlaylist`](ue_ue.MediaPlaylist.md)

#### Defined in

[ue/ue.d.ts:50218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50218)

___

### GetPlaylistIndex

▸ **GetPlaylistIndex**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50219)

___

### GetRate

▸ **GetRate**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50220)

___

### GetSelectedTrack

▸ **GetSelectedTrack**(`TrackType`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50221)

___

### GetSupportedRates

▸ **GetSupportedRates**(`OutRates`, `Unthinned`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutRates` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`FloatRange`](ue_ue.FloatRange.md)\>\> |
| `Unthinned` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:50222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50222)

___

### GetTime

▸ **GetTime**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

#### Defined in

[ue/ue.d.ts:50223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50223)

___

### GetTimeDelay

▸ **GetTimeDelay**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

#### Defined in

[ue/ue.d.ts:50224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50224)

___

### GetTrackDisplayName

▸ **GetTrackDisplayName**(`TrackType`, `TrackIndex`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |
| `TrackIndex` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:50225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50225)

___

### GetTrackFormat

▸ **GetTrackFormat**(`TrackType`, `TrackIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |
| `TrackIndex` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50226](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50226)

___

### GetTrackLanguage

▸ **GetTrackLanguage**(`TrackType`, `TrackIndex`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |
| `TrackIndex` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:50227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50227)

___

### GetUrl

▸ **GetUrl**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:50228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50228)

___

### GetVerticalFieldOfView

▸ **GetVerticalFieldOfView**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50229)

___

### GetVideoTrackAspectRatio

▸ **GetVideoTrackAspectRatio**(`TrackIndex`, `FormatIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50230](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50230)

___

### GetVideoTrackDimensions

▸ **GetVideoTrackDimensions**(`TrackIndex`, `FormatIndex`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:50231](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50231)

___

### GetVideoTrackFrameRate

▸ **GetVideoTrackFrameRate**(`TrackIndex`, `FormatIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50232](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50232)

___

### GetVideoTrackFrameRates

▸ **GetVideoTrackFrameRates**(`TrackIndex`, `FormatIndex`): [`FloatRange`](ue_ue.FloatRange.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

[`FloatRange`](ue_ue.FloatRange.md)

#### Defined in

[ue/ue.d.ts:50233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50233)

___

### GetVideoTrackType

▸ **GetVideoTrackType**(`TrackIndex`, `FormatIndex`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:50234](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50234)

___

### GetViewRotation

▸ **GetViewRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:50235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50235)

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

### HasError

▸ **HasError**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50236)

___

### IsBuffering

▸ **IsBuffering**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50237)

___

### IsClosed

▸ **IsClosed**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50238](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50238)

___

### IsConnecting

▸ **IsConnecting**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50239)

___

### IsLooping

▸ **IsLooping**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50240](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50240)

___

### IsPaused

▸ **IsPaused**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50241](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50241)

___

### IsPlaying

▸ **IsPlaying**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50242)

___

### IsPreparing

▸ **IsPreparing**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50243)

___

### IsReady

▸ **IsReady**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50244)

___

### Next

▸ **Next**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50245)

___

### OpenFile

▸ **OpenFile**(`FilePath`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FilePath` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50246)

___

### OpenPlaylist

▸ **OpenPlaylist**(`InPlaylist`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPlaylist` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaPlaylist`](ue_ue.MediaPlaylist.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50247](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50247)

___

### OpenPlaylistIndex

▸ **OpenPlaylistIndex**(`InPlaylist`, `Index`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPlaylist` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaPlaylist`](ue_ue.MediaPlaylist.md)\> |
| `Index` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50248)

___

### OpenSource

▸ **OpenSource**(`MediaSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50249)

___

### OpenSourceLatent

▸ **OpenSourceLatent**(`WorldContextObject`, `LatentInfo`, `MediaSource`, `Options`, `bSuccess`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LatentInfo` | [`LatentActionInfo`](ue_ue.LatentActionInfo.md) |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |
| `Options` | [`MediaPlayerOptions`](ue_ue.MediaPlayerOptions.md) |
| `bSuccess` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:50250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50250)

___

### OpenSourceWithOptions

▸ **OpenSourceWithOptions**(`MediaSource`, `Options`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |
| `Options` | [`MediaPlayerOptions`](ue_ue.MediaPlayerOptions.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50251)

___

### OpenUrl

▸ **OpenUrl**(`Url`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Url` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50252](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50252)

___

### Pause

▸ **Pause**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50253](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50253)

___

### Play

▸ **Play**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50254)

___

### Previous

▸ **Previous**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50255](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50255)

___

### Reopen

▸ **Reopen**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50256](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50256)

___

### Rewind

▸ **Rewind**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50257](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50257)

___

### Seek

▸ **Seek**(`Time`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | [`Timespan`](ue_ue.Timespan.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50258](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50258)

___

### SelectTrack

▸ **SelectTrack**(`TrackType`, `TrackIndex`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |
| `TrackIndex` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50259](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50259)

___

### SetBlockOnTime

▸ **SetBlockOnTime**(`Time`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | [`Timespan`](ue_ue.Timespan.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:50260](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50260)

___

### SetDesiredPlayerName

▸ **SetDesiredPlayerName**(`PlayerName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:50261](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50261)

___

### SetLooping

▸ **SetLooping**(`Looping`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Looping` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50262](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50262)

___

### SetMediaOptions

▸ **SetMediaOptions**(`Options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Options` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:50263](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50263)

___

### SetNativeVolume

▸ **SetNativeVolume**(`Volume`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Volume` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50264](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50264)

___

### SetRate

▸ **SetRate**(`Rate`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rate` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50265](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50265)

___

### SetTimeDelay

▸ **SetTimeDelay**(`TimeDelay`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeDelay` | [`Timespan`](ue_ue.Timespan.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:50266](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50266)

___

### SetTrackFormat

▸ **SetTrackFormat**(`TrackType`, `TrackIndex`, `FormatIndex`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50267](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50267)

___

### SetVideoTrackFrameRate

▸ **SetVideoTrackFrameRate**(`TrackIndex`, `FormatIndex`, `FrameRate`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |
| `FrameRate` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50268](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50268)

___

### SetViewField

▸ **SetViewField**(`Horizontal`, `Vertical`, `Absolute`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Horizontal` | `number` |
| `Vertical` | `number` |
| `Absolute` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50269](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50269)

___

### SetViewRotation

▸ **SetViewRotation**(`Rotation`, `Absolute`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Absolute` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50270)

___

### SupportsRate

▸ **SupportsRate**(`Rate`, `Unthinned`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rate` | `number` |
| `Unthinned` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50271](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50271)

___

### SupportsScrubbing

▸ **SupportsScrubbing**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50272)

___

### SupportsSeeking

▸ **SupportsSeeking**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50273](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50273)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MediaPlayer`](ue_ue.MediaPlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MediaPlayer`](ue_ue.MediaPlayer.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:50275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50275)

___

### Load

▸ `Static` **Load**(`InName`): [`MediaPlayer`](ue_ue.MediaPlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MediaPlayer`](ue_ue.MediaPlayer.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:50276](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50276)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:50274](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50274)
