[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WindowsTargetSettings

# Class: WindowsTargetSettings

[ue/ue](../modules/ue_ue.md).WindowsTargetSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`WindowsTargetSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.WindowsTargetSettings.md#constructor)

### Properties

- [AudioCallbackBufferFrameSize](ue_ue.WindowsTargetSettings.md#audiocallbackbufferframesize)
- [AudioMaxChannels](ue_ue.WindowsTargetSettings.md#audiomaxchannels)
- [AudioNumBuffersToEnqueue](ue_ue.WindowsTargetSettings.md#audionumbufferstoenqueue)
- [AudioNumSourceWorkers](ue_ue.WindowsTargetSettings.md#audionumsourceworkers)
- [AudioSampleRate](ue_ue.WindowsTargetSettings.md#audiosamplerate)
- [AutoStreamingThreshold](ue_ue.WindowsTargetSettings.md#autostreamingthreshold)
- [CacheSizeKB](ue_ue.WindowsTargetSettings.md#cachesizekb)
- [ChunkSizeKB](ue_ue.WindowsTargetSettings.md#chunksizekb)
- [Compiler](ue_ue.WindowsTargetSettings.md#compiler)
- [CompressionOverrides](ue_ue.WindowsTargetSettings.md#compressionoverrides)
- [CompressionQualityModifier](ue_ue.WindowsTargetSettings.md#compressionqualitymodifier)
- [DefaultGraphicsRHI](ue_ue.WindowsTargetSettings.md#defaultgraphicsrhi)
- [HighSampleRate](ue_ue.WindowsTargetSettings.md#highsamplerate)
- [LowSampleRate](ue_ue.WindowsTargetSettings.md#lowsamplerate)
- [MaxSampleRate](ue_ue.WindowsTargetSettings.md#maxsamplerate)
- [MedSampleRate](ue_ue.WindowsTargetSettings.md#medsamplerate)
- [MinSampleRate](ue_ue.WindowsTargetSettings.md#minsamplerate)
- [MinimumOSVersion](ue_ue.WindowsTargetSettings.md#minimumosversion)
- [OcclusionPlugin](ue_ue.WindowsTargetSettings.md#occlusionplugin)
- [ReverbPlugin](ue_ue.WindowsTargetSettings.md#reverbplugin)
- [SoundCueCookQualityIndex](ue_ue.WindowsTargetSettings.md#soundcuecookqualityindex)
- [SpatializationPlugin](ue_ue.WindowsTargetSettings.md#spatializationplugin)
- [TargetedRHIs](ue_ue.WindowsTargetSettings.md#targetedrhis)
- [\_\_tid\_Object\_\_](ue_ue.WindowsTargetSettings.md#__tid_object__)
- [\_\_tid\_WindowsTargetSettings\_\_](ue_ue.WindowsTargetSettings.md#__tid_windowstargetsettings__)
- [bResampleForDevice](ue_ue.WindowsTargetSettings.md#bresamplefordevice)
- [bUseAudioStreamCaching](ue_ue.WindowsTargetSettings.md#buseaudiostreamcaching)

### Methods

- [CreateDefaultSubobject](ue_ue.WindowsTargetSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WindowsTargetSettings.md#executeubergraph)
- [GetClass](ue_ue.WindowsTargetSettings.md#getclass)
- [GetName](ue_ue.WindowsTargetSettings.md#getname)
- [GetOuter](ue_ue.WindowsTargetSettings.md#getouter)
- [GetWorld](ue_ue.WindowsTargetSettings.md#getworld)
- [Find](ue_ue.WindowsTargetSettings.md#find)
- [Load](ue_ue.WindowsTargetSettings.md#load)
- [StaticClass](ue_ue.WindowsTargetSettings.md#staticclass)

## Constructors

### constructor

• **new WindowsTargetSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AudioCallbackBufferFrameSize

• **AudioCallbackBufferFrameSize**: `number`

___

### AudioMaxChannels

• **AudioMaxChannels**: `number`

___

### AudioNumBuffersToEnqueue

• **AudioNumBuffersToEnqueue**: `number`

___

### AudioNumSourceWorkers

• **AudioNumSourceWorkers**: `number`

___

### AudioSampleRate

• **AudioSampleRate**: `number`

___

### AutoStreamingThreshold

• **AutoStreamingThreshold**: `number`

___

### CacheSizeKB

• **CacheSizeKB**: `number`

___

### ChunkSizeKB

• **ChunkSizeKB**: `number`

___

### Compiler

• **Compiler**: [`ECompilerVersion`](../enums/ue_ue.ECompilerVersion.md)

___

### CompressionOverrides

• **CompressionOverrides**: [`PlatformRuntimeAudioCompressionOverrides`](ue_ue.PlatformRuntimeAudioCompressionOverrides.md)

___

### CompressionQualityModifier

• **CompressionQualityModifier**: `number`

___

### DefaultGraphicsRHI

• **DefaultGraphicsRHI**: [`EDefaultGraphicsRHI`](../enums/ue_ue.EDefaultGraphicsRHI.md)

___

### HighSampleRate

• **HighSampleRate**: `number`

___

### LowSampleRate

• **LowSampleRate**: `number`

___

### MaxSampleRate

• **MaxSampleRate**: `number`

___

### MedSampleRate

• **MedSampleRate**: `number`

___

### MinSampleRate

• **MinSampleRate**: `number`

___

### MinimumOSVersion

• **MinimumOSVersion**: [`EMinimumSupportedOS`](../enums/ue_ue.EMinimumSupportedOS.md)

___

### OcclusionPlugin

• **OcclusionPlugin**: `string`

___

### ReverbPlugin

• **ReverbPlugin**: `string`

___

### SoundCueCookQualityIndex

• **SoundCueCookQualityIndex**: `number`

___

### SpatializationPlugin

• **SpatializationPlugin**: `string`

___

### TargetedRHIs

• **TargetedRHIs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_WindowsTargetSettings\_\_

• **\_\_tid\_WindowsTargetSettings\_\_**: `boolean`

___

### bResampleForDevice

• **bResampleForDevice**: `boolean`

___

### bUseAudioStreamCaching

• **bUseAudioStreamCaching**: `boolean`

## Methods

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

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WindowsTargetSettings`](ue_ue.WindowsTargetSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WindowsTargetSettings`](ue_ue.WindowsTargetSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`WindowsTargetSettings`](ue_ue.WindowsTargetSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WindowsTargetSettings`](ue_ue.WindowsTargetSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
