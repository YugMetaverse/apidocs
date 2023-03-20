[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundWave

# Class: SoundWave

[ue/ue](../modules/ue_ue.md).SoundWave

## Hierarchy

- [`SoundBase`](ue_ue.SoundBase.md)

  ↳ **`SoundWave`**

  ↳↳ [`SoundSourceBus`](ue_ue.SoundSourceBus.md)

  ↳↳ [`SoundWaveProcedural`](ue_ue.SoundWaveProcedural.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SoundWave.md#constructor)

### Properties

- [AssetImportData](ue_ue.SoundWave.md#assetimportdata)
- [AttenuationSettings](ue_ue.SoundWave.md#attenuationsettings)
- [BusSends](ue_ue.SoundWave.md#bussends)
- [ChannelOffsets](ue_ue.SoundWave.md#channeloffsets)
- [ChannelSizes](ue_ue.SoundWave.md#channelsizes)
- [Comment](ue_ue.SoundWave.md#comment)
- [CompressionQuality](ue_ue.SoundWave.md#compressionquality)
- [ConcurrencyOverrides](ue_ue.SoundWave.md#concurrencyoverrides)
- [ConcurrencySet](ue_ue.SoundWave.md#concurrencyset)
- [CookedEnvelopeTimeData](ue_ue.SoundWave.md#cookedenvelopetimedata)
- [CookedSpectralTimeData](ue_ue.SoundWave.md#cookedspectraltimedata)
- [Curves](ue_ue.SoundWave.md#curves)
- [Duration](ue_ue.SoundWave.md#duration)
- [EnvelopeFollowerAttackTime](ue_ue.SoundWave.md#envelopefollowerattacktime)
- [EnvelopeFollowerFrameSize](ue_ue.SoundWave.md#envelopefollowerframesize)
- [EnvelopeFollowerReleaseTime](ue_ue.SoundWave.md#envelopefollowerreleasetime)
- [FFTAnalysisAttackTime](ue_ue.SoundWave.md#fftanalysisattacktime)
- [FFTAnalysisFrameSize](ue_ue.SoundWave.md#fftanalysisframesize)
- [FFTAnalysisReleaseTime](ue_ue.SoundWave.md#fftanalysisreleasetime)
- [FFTSize](ue_ue.SoundWave.md#fftsize)
- [FrequenciesToAnalyze](ue_ue.SoundWave.md#frequenciestoanalyze)
- [InitialChunkSize](ue_ue.SoundWave.md#initialchunksize)
- [InternalCurves](ue_ue.SoundWave.md#internalcurves)
- [LoadingBehavior](ue_ue.SoundWave.md#loadingbehavior)
- [MaxConcurrentPlayCount](ue_ue.SoundWave.md#maxconcurrentplaycount)
- [MaxConcurrentResolutionRule](ue_ue.SoundWave.md#maxconcurrentresolutionrule)
- [MaxDistance](ue_ue.SoundWave.md#maxdistance)
- [Modulation](ue_ue.SoundWave.md#modulation)
- [NumChannels](ue_ue.SoundWave.md#numchannels)
- [OverrideSoundToUseForAnalysis](ue_ue.SoundWave.md#overridesoundtouseforanalysis)
- [Pitch](ue_ue.SoundWave.md#pitch)
- [PreEffectBusSends](ue_ue.SoundWave.md#preeffectbussends)
- [Priority](ue_ue.SoundWave.md#priority)
- [SampleRate](ue_ue.SoundWave.md#samplerate)
- [SampleRateQuality](ue_ue.SoundWave.md#sampleratequality)
- [SoundClassObject](ue_ue.SoundWave.md#soundclassobject)
- [SoundConcurrencySettings](ue_ue.SoundWave.md#soundconcurrencysettings)
- [SoundGroup](ue_ue.SoundWave.md#soundgroup)
- [SoundSubmixObject](ue_ue.SoundWave.md#soundsubmixobject)
- [SoundSubmixSends](ue_ue.SoundWave.md#soundsubmixsends)
- [SourceEffectChain](ue_ue.SoundWave.md#sourceeffectchain)
- [SourceFilePath](ue_ue.SoundWave.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.SoundWave.md#sourcefiletimestamp)
- [SpokenText](ue_ue.SoundWave.md#spokentext)
- [StreamingPriority](ue_ue.SoundWave.md#streamingpriority)
- [SubtitlePriority](ue_ue.SoundWave.md#subtitlepriority)
- [Subtitles](ue_ue.SoundWave.md#subtitles)
- [TotalSamples](ue_ue.SoundWave.md#totalsamples)
- [TreatFileAsLoopingForAnalysis](ue_ue.SoundWave.md#treatfileasloopingforanalysis)
- [VirtualizationMode](ue_ue.SoundWave.md#virtualizationmode)
- [Volume](ue_ue.SoundWave.md#volume)
- [\_\_tid\_Object\_\_](ue_ue.SoundWave.md#__tid_object__)
- [\_\_tid\_SoundBase\_\_](ue_ue.SoundWave.md#__tid_soundbase__)
- [\_\_tid\_SoundWave\_\_](ue_ue.SoundWave.md#__tid_soundwave__)
- [bBypassVolumeScaleForPriority](ue_ue.SoundWave.md#bbypassvolumescaleforpriority)
- [bDebug](ue_ue.SoundWave.md#bdebug)
- [bEnableAmplitudeEnvelopeAnalysis](ue_ue.SoundWave.md#benableamplitudeenvelopeanalysis)
- [bEnableBakedFFTAnalysis](ue_ue.SoundWave.md#benablebakedfftanalysis)
- [bHasConcatenatorNode](ue_ue.SoundWave.md#bhasconcatenatornode)
- [bHasDelayNode](ue_ue.SoundWave.md#bhasdelaynode)
- [bHasVirtualizeWhenSilent](ue_ue.SoundWave.md#bhasvirtualizewhensilent)
- [bIsAmbisonics](ue_ue.SoundWave.md#bisambisonics)
- [bLooping](ue_ue.SoundWave.md#blooping)
- [bManualWordWrap](ue_ue.SoundWave.md#bmanualwordwrap)
- [bMature](ue_ue.SoundWave.md#bmature)
- [bOutputToBusOnly](ue_ue.SoundWave.md#boutputtobusonly)
- [bOverrideConcurrency](ue_ue.SoundWave.md#boverrideconcurrency)
- [bSeekableStreaming](ue_ue.SoundWave.md#bseekablestreaming)
- [bSingleLine](ue_ue.SoundWave.md#bsingleline)
- [bStreaming](ue_ue.SoundWave.md#bstreaming)
- [bVirtualizeWhenSilent](ue_ue.SoundWave.md#bvirtualizewhensilent)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundWave.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundWave.md#executeubergraph)
- [GetClass](ue_ue.SoundWave.md#getclass)
- [GetName](ue_ue.SoundWave.md#getname)
- [GetOuter](ue_ue.SoundWave.md#getouter)
- [GetWorld](ue_ue.SoundWave.md#getworld)
- [Find](ue_ue.SoundWave.md#find)
- [Load](ue_ue.SoundWave.md#load)
- [StaticClass](ue_ue.SoundWave.md#staticclass)

## Constructors

### constructor

• **new SoundWave**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[constructor](ue_ue.SoundBase.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[AttenuationSettings](ue_ue.SoundBase.md#attenuationsettings)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[BusSends](ue_ue.SoundBase.md#bussends)

___

### ChannelOffsets

• **ChannelOffsets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### ChannelSizes

• **ChannelSizes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### Comment

• **Comment**: `string`

___

### CompressionQuality

• **CompressionQuality**: `number`

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[ConcurrencyOverrides](ue_ue.SoundBase.md#concurrencyoverrides)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[ConcurrencySet](ue_ue.SoundBase.md#concurrencyset)

___

### CookedEnvelopeTimeData

• **CookedEnvelopeTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveEnvelopeTimeData`](ue_ue.SoundWaveEnvelopeTimeData.md)\>

___

### CookedSpectralTimeData

• **CookedSpectralTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveSpectralTimeData`](ue_ue.SoundWaveSpectralTimeData.md)\>

___

### Curves

• **Curves**: [`CurveTable`](ue_ue.CurveTable.md)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Duration](ue_ue.SoundBase.md#duration)

___

### EnvelopeFollowerAttackTime

• **EnvelopeFollowerAttackTime**: `number`

___

### EnvelopeFollowerFrameSize

• **EnvelopeFollowerFrameSize**: `number`

___

### EnvelopeFollowerReleaseTime

• **EnvelopeFollowerReleaseTime**: `number`

___

### FFTAnalysisAttackTime

• **FFTAnalysisAttackTime**: `number`

___

### FFTAnalysisFrameSize

• **FFTAnalysisFrameSize**: `number`

___

### FFTAnalysisReleaseTime

• **FFTAnalysisReleaseTime**: `number`

___

### FFTSize

• **FFTSize**: [`ESoundWaveFFTSize`](../enums/ue_ue.ESoundWaveFFTSize.md)

___

### FrequenciesToAnalyze

• **FrequenciesToAnalyze**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### InitialChunkSize

• **InitialChunkSize**: `number`

___

### InternalCurves

• **InternalCurves**: [`CurveTable`](ue_ue.CurveTable.md)

___

### LoadingBehavior

• **LoadingBehavior**: [`ESoundWaveLoadingBehavior`](../enums/ue_ue.ESoundWaveLoadingBehavior.md)

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxConcurrentPlayCount](ue_ue.SoundBase.md#maxconcurrentplaycount)

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxConcurrentResolutionRule](ue_ue.SoundBase.md#maxconcurrentresolutionrule)

___

### MaxDistance

• **MaxDistance**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxDistance](ue_ue.SoundBase.md#maxdistance)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Modulation](ue_ue.SoundBase.md#modulation)

___

### NumChannels

• **NumChannels**: `number`

___

### OverrideSoundToUseForAnalysis

• **OverrideSoundToUseForAnalysis**: [`SoundWave`](ue_ue.SoundWave.md)

___

### Pitch

• **Pitch**: `number`

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[PreEffectBusSends](ue_ue.SoundBase.md#preeffectbussends)

___

### Priority

• **Priority**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Priority](ue_ue.SoundBase.md#priority)

___

### SampleRate

• **SampleRate**: `number`

___

### SampleRateQuality

• **SampleRateQuality**: [`ESoundwaveSampleRateSettings`](../enums/ue_ue.ESoundwaveSampleRateSettings.md)

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundClassObject](ue_ue.SoundBase.md#soundclassobject)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundConcurrencySettings](ue_ue.SoundBase.md#soundconcurrencysettings)

___

### SoundGroup

• **SoundGroup**: [`ESoundGroup`](../enums/ue_ue.ESoundGroup.md)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundSubmixObject](ue_ue.SoundBase.md#soundsubmixobject)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundSubmixSends](ue_ue.SoundBase.md#soundsubmixsends)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SourceEffectChain](ue_ue.SoundBase.md#sourceeffectchain)

___

### SourceFilePath

• **SourceFilePath**: `string`

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

___

### SpokenText

• **SpokenText**: `string`

___

### StreamingPriority

• **StreamingPriority**: `number`

___

### SubtitlePriority

• **SubtitlePriority**: `number`

___

### Subtitles

• **Subtitles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubtitleCue`](ue_ue.SubtitleCue.md)\>

___

### TotalSamples

• **TotalSamples**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[TotalSamples](ue_ue.SoundBase.md#totalsamples)

___

### TreatFileAsLoopingForAnalysis

• **TreatFileAsLoopingForAnalysis**: `boolean`

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[VirtualizationMode](ue_ue.SoundBase.md#virtualizationmode)

___

### Volume

• **Volume**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[__tid_Object__](ue_ue.SoundBase.md#__tid_object__)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[__tid_SoundBase__](ue_ue.SoundBase.md#__tid_soundbase__)

___

### \_\_tid\_SoundWave\_\_

• **\_\_tid\_SoundWave\_\_**: `boolean`

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bBypassVolumeScaleForPriority](ue_ue.SoundBase.md#bbypassvolumescaleforpriority)

___

### bDebug

• **bDebug**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bDebug](ue_ue.SoundBase.md#bdebug)

___

### bEnableAmplitudeEnvelopeAnalysis

• **bEnableAmplitudeEnvelopeAnalysis**: `boolean`

___

### bEnableBakedFFTAnalysis

• **bEnableBakedFFTAnalysis**: `boolean`

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasConcatenatorNode](ue_ue.SoundBase.md#bhasconcatenatornode)

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasDelayNode](ue_ue.SoundBase.md#bhasdelaynode)

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasVirtualizeWhenSilent](ue_ue.SoundBase.md#bhasvirtualizewhensilent)

___

### bIsAmbisonics

• **bIsAmbisonics**: `boolean`

___

### bLooping

• **bLooping**: `boolean`

___

### bManualWordWrap

• **bManualWordWrap**: `boolean`

___

### bMature

• **bMature**: `boolean`

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bOutputToBusOnly](ue_ue.SoundBase.md#boutputtobusonly)

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bOverrideConcurrency](ue_ue.SoundBase.md#boverrideconcurrency)

___

### bSeekableStreaming

• **bSeekableStreaming**: `boolean`

___

### bSingleLine

• **bSingleLine**: `boolean`

___

### bStreaming

• **bStreaming**: `boolean`

___

### bVirtualizeWhenSilent

• **bVirtualizeWhenSilent**: `boolean`

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

[SoundBase](ue_ue.SoundBase.md).[CreateDefaultSubobject](ue_ue.SoundBase.md#createdefaultsubobject)

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

[SoundBase](ue_ue.SoundBase.md).[ExecuteUbergraph](ue_ue.SoundBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetClass](ue_ue.SoundBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetName](ue_ue.SoundBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetOuter](ue_ue.SoundBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetWorld](ue_ue.SoundBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundWave`](ue_ue.SoundWave.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundWave`](ue_ue.SoundWave.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[Find](ue_ue.SoundBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundWave`](ue_ue.SoundWave.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundWave`](ue_ue.SoundWave.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[Load](ue_ue.SoundBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[StaticClass](ue_ue.SoundBase.md#staticclass)
