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

## Properties

### AffectedByPIEHandling

• **AffectedByPIEHandling**: `boolean`

___

### CacheAhead

• **CacheAhead**: [`Timespan`](ue_ue.Timespan.md)

___

### CacheBehind

• **CacheBehind**: [`Timespan`](ue_ue.Timespan.md)

___

### CacheBehindGame

• **CacheBehindGame**: [`Timespan`](ue_ue.Timespan.md)

___

### HorizontalFieldOfView

• **HorizontalFieldOfView**: `number`

___

### Loop

• **Loop**: `boolean`

___

### NativeAudioOut

• **NativeAudioOut**: `boolean`

___

### OnEndReached

• **OnEndReached**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnMediaClosed

• **OnMediaClosed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnMediaOpenFailed

• **OnMediaOpenFailed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`FailedUrl`: `string`) => `void`\>

___

### OnMediaOpened

• **OnMediaOpened**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`OpenedUrl`: `string`) => `void`\>

___

### OnPlaybackResumed

• **OnPlaybackResumed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnPlaybackSuspended

• **OnPlaybackSuspended**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnSeekCompleted

• **OnSeekCompleted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnTracksChanged

• **OnTracksChanged**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### PlayOnOpen

• **PlayOnOpen**: `boolean`

___

### PlayerGuid

• **PlayerGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### Playlist

• **Playlist**: [`MediaPlaylist`](ue_ue.MediaPlaylist.md)

___

### PlaylistIndex

• **PlaylistIndex**: `number`

___

### Shuffle

• **Shuffle**: `boolean`

___

### TimeDelay

• **TimeDelay**: [`Timespan`](ue_ue.Timespan.md)

___

### VerticalFieldOfView

• **VerticalFieldOfView**: `number`

___

### ViewRotation

• **ViewRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### \_\_tid\_MediaPlayer\_\_

• **\_\_tid\_MediaPlayer\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

## Methods

### CanPause

▸ **CanPause**(): `boolean`

#### Returns

`boolean`

___

### CanPlaySource

▸ **CanPlaySource**(`MediaSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`boolean`

___

### CanPlayUrl

▸ **CanPlayUrl**(`Url`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Url` | `string` |

#### Returns

`boolean`

___

### Close

▸ **Close**(): `void`

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

### GetAudioTrackChannels

▸ **GetAudioTrackChannels**(`TrackIndex`, `FormatIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackIndex` | `number` |
| `FormatIndex` | `number` |

#### Returns

`number`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetDesiredPlayerName

▸ **GetDesiredPlayerName**(): `string`

#### Returns

`string`

___

### GetDuration

▸ **GetDuration**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

___

### GetHorizontalFieldOfView

▸ **GetHorizontalFieldOfView**(): `number`

#### Returns

`number`

___

### GetLastAudioSampleProcessedTime

▸ **GetLastAudioSampleProcessedTime**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

___

### GetLastVideoSampleProcessedTime

▸ **GetLastVideoSampleProcessedTime**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

___

### GetMediaName

▸ **GetMediaName**(): `string`

#### Returns

`string`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

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

___

### GetNumTracks

▸ **GetNumTracks**(`TrackType`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |

#### Returns

`number`

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetPlayerName

▸ **GetPlayerName**(): `string`

#### Returns

`string`

___

### GetPlaylist

▸ **GetPlaylist**(): [`MediaPlaylist`](ue_ue.MediaPlaylist.md)

#### Returns

[`MediaPlaylist`](ue_ue.MediaPlaylist.md)

___

### GetPlaylistIndex

▸ **GetPlaylistIndex**(): `number`

#### Returns

`number`

___

### GetRate

▸ **GetRate**(): `number`

#### Returns

`number`

___

### GetSelectedTrack

▸ **GetSelectedTrack**(`TrackType`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrackType` | [`EMediaPlayerTrack`](../enums/ue_ue.EMediaPlayerTrack.md) |

#### Returns

`number`

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

___

### GetTime

▸ **GetTime**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

___

### GetTimeDelay

▸ **GetTimeDelay**(): [`Timespan`](ue_ue.Timespan.md)

#### Returns

[`Timespan`](ue_ue.Timespan.md)

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

___

### GetUrl

▸ **GetUrl**(): `string`

#### Returns

`string`

___

### GetVerticalFieldOfView

▸ **GetVerticalFieldOfView**(): `number`

#### Returns

`number`

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

___

### GetViewRotation

▸ **GetViewRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### HasError

▸ **HasError**(): `boolean`

#### Returns

`boolean`

___

### IsBuffering

▸ **IsBuffering**(): `boolean`

#### Returns

`boolean`

___

### IsClosed

▸ **IsClosed**(): `boolean`

#### Returns

`boolean`

___

### IsConnecting

▸ **IsConnecting**(): `boolean`

#### Returns

`boolean`

___

### IsLooping

▸ **IsLooping**(): `boolean`

#### Returns

`boolean`

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

### IsPreparing

▸ **IsPreparing**(): `boolean`

#### Returns

`boolean`

___

### IsReady

▸ **IsReady**(): `boolean`

#### Returns

`boolean`

___

### Next

▸ **Next**(): `boolean`

#### Returns

`boolean`

___

### OpenFile

▸ **OpenFile**(`FilePath`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FilePath` | `string` |

#### Returns

`boolean`

___

### OpenPlaylist

▸ **OpenPlaylist**(`InPlaylist`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPlaylist` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaPlaylist`](ue_ue.MediaPlaylist.md)\> |

#### Returns

`boolean`

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

___

### OpenSource

▸ **OpenSource**(`MediaSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`boolean`

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

___

### OpenUrl

▸ **OpenUrl**(`Url`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Url` | `string` |

#### Returns

`boolean`

___

### Pause

▸ **Pause**(): `boolean`

#### Returns

`boolean`

___

### Play

▸ **Play**(): `boolean`

#### Returns

`boolean`

___

### Previous

▸ **Previous**(): `boolean`

#### Returns

`boolean`

___

### Reopen

▸ **Reopen**(): `boolean`

#### Returns

`boolean`

___

### Rewind

▸ **Rewind**(): `boolean`

#### Returns

`boolean`

___

### Seek

▸ **Seek**(`Time`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | [`Timespan`](ue_ue.Timespan.md) |

#### Returns

`boolean`

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

___

### SetBlockOnTime

▸ **SetBlockOnTime**(`Time`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Time` | [`Timespan`](ue_ue.Timespan.md) |

#### Returns

`void`

___

### SetDesiredPlayerName

▸ **SetDesiredPlayerName**(`PlayerName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlayerName` | `string` |

#### Returns

`void`

___

### SetLooping

▸ **SetLooping**(`Looping`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Looping` | `boolean` |

#### Returns

`boolean`

___

### SetMediaOptions

▸ **SetMediaOptions**(`Options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Options` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`void`

___

### SetNativeVolume

▸ **SetNativeVolume**(`Volume`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Volume` | `number` |

#### Returns

`boolean`

___

### SetRate

▸ **SetRate**(`Rate`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rate` | `number` |

#### Returns

`boolean`

___

### SetTimeDelay

▸ **SetTimeDelay**(`TimeDelay`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeDelay` | [`Timespan`](ue_ue.Timespan.md) |

#### Returns

`void`

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

___

### SupportsScrubbing

▸ **SupportsScrubbing**(): `boolean`

#### Returns

`boolean`

___

### SupportsSeeking

▸ **SupportsSeeking**(): `boolean`

#### Returns

`boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
