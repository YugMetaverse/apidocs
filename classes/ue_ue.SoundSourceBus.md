[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundSourceBus

# Class: SoundSourceBus

[ue/ue](../modules/ue_ue.md).SoundSourceBus

## Hierarchy

- [`SoundWave`](ue_ue.SoundWave.md)

  ↳ **`SoundSourceBus`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundSourceBus.md#constructor)

### Properties

- [AssetImportData](ue_ue.SoundSourceBus.md#assetimportdata)
- [AttenuationSettings](ue_ue.SoundSourceBus.md#attenuationsettings)
- [BusSends](ue_ue.SoundSourceBus.md#bussends)
- [ChannelOffsets](ue_ue.SoundSourceBus.md#channeloffsets)
- [ChannelSizes](ue_ue.SoundSourceBus.md#channelsizes)
- [Comment](ue_ue.SoundSourceBus.md#comment)
- [CompressionQuality](ue_ue.SoundSourceBus.md#compressionquality)
- [ConcurrencyOverrides](ue_ue.SoundSourceBus.md#concurrencyoverrides)
- [ConcurrencySet](ue_ue.SoundSourceBus.md#concurrencyset)
- [CookedEnvelopeTimeData](ue_ue.SoundSourceBus.md#cookedenvelopetimedata)
- [CookedSpectralTimeData](ue_ue.SoundSourceBus.md#cookedspectraltimedata)
- [Curves](ue_ue.SoundSourceBus.md#curves)
- [Duration](ue_ue.SoundSourceBus.md#duration)
- [EnvelopeFollowerAttackTime](ue_ue.SoundSourceBus.md#envelopefollowerattacktime)
- [EnvelopeFollowerFrameSize](ue_ue.SoundSourceBus.md#envelopefollowerframesize)
- [EnvelopeFollowerReleaseTime](ue_ue.SoundSourceBus.md#envelopefollowerreleasetime)
- [FFTAnalysisAttackTime](ue_ue.SoundSourceBus.md#fftanalysisattacktime)
- [FFTAnalysisFrameSize](ue_ue.SoundSourceBus.md#fftanalysisframesize)
- [FFTAnalysisReleaseTime](ue_ue.SoundSourceBus.md#fftanalysisreleasetime)
- [FFTSize](ue_ue.SoundSourceBus.md#fftsize)
- [FrequenciesToAnalyze](ue_ue.SoundSourceBus.md#frequenciestoanalyze)
- [InitialChunkSize](ue_ue.SoundSourceBus.md#initialchunksize)
- [InternalCurves](ue_ue.SoundSourceBus.md#internalcurves)
- [LoadingBehavior](ue_ue.SoundSourceBus.md#loadingbehavior)
- [MaxConcurrentPlayCount](ue_ue.SoundSourceBus.md#maxconcurrentplaycount)
- [MaxConcurrentResolutionRule](ue_ue.SoundSourceBus.md#maxconcurrentresolutionrule)
- [MaxDistance](ue_ue.SoundSourceBus.md#maxdistance)
- [Modulation](ue_ue.SoundSourceBus.md#modulation)
- [NumChannels](ue_ue.SoundSourceBus.md#numchannels)
- [OverrideSoundToUseForAnalysis](ue_ue.SoundSourceBus.md#overridesoundtouseforanalysis)
- [Pitch](ue_ue.SoundSourceBus.md#pitch)
- [PreEffectBusSends](ue_ue.SoundSourceBus.md#preeffectbussends)
- [Priority](ue_ue.SoundSourceBus.md#priority)
- [SampleRate](ue_ue.SoundSourceBus.md#samplerate)
- [SampleRateQuality](ue_ue.SoundSourceBus.md#sampleratequality)
- [SoundClassObject](ue_ue.SoundSourceBus.md#soundclassobject)
- [SoundConcurrencySettings](ue_ue.SoundSourceBus.md#soundconcurrencysettings)
- [SoundGroup](ue_ue.SoundSourceBus.md#soundgroup)
- [SoundSubmixObject](ue_ue.SoundSourceBus.md#soundsubmixobject)
- [SoundSubmixSends](ue_ue.SoundSourceBus.md#soundsubmixsends)
- [SourceBusChannels](ue_ue.SoundSourceBus.md#sourcebuschannels)
- [SourceBusDuration](ue_ue.SoundSourceBus.md#sourcebusduration)
- [SourceEffectChain](ue_ue.SoundSourceBus.md#sourceeffectchain)
- [SourceFilePath](ue_ue.SoundSourceBus.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.SoundSourceBus.md#sourcefiletimestamp)
- [SpokenText](ue_ue.SoundSourceBus.md#spokentext)
- [StreamingPriority](ue_ue.SoundSourceBus.md#streamingpriority)
- [SubtitlePriority](ue_ue.SoundSourceBus.md#subtitlepriority)
- [Subtitles](ue_ue.SoundSourceBus.md#subtitles)
- [TotalSamples](ue_ue.SoundSourceBus.md#totalsamples)
- [TreatFileAsLoopingForAnalysis](ue_ue.SoundSourceBus.md#treatfileasloopingforanalysis)
- [VirtualizationMode](ue_ue.SoundSourceBus.md#virtualizationmode)
- [Volume](ue_ue.SoundSourceBus.md#volume)
- [\_\_tid\_Object\_\_](ue_ue.SoundSourceBus.md#__tid_object__)
- [\_\_tid\_SoundBase\_\_](ue_ue.SoundSourceBus.md#__tid_soundbase__)
- [\_\_tid\_SoundSourceBus\_\_](ue_ue.SoundSourceBus.md#__tid_soundsourcebus__)
- [\_\_tid\_SoundWave\_\_](ue_ue.SoundSourceBus.md#__tid_soundwave__)
- [bAutoDeactivateWhenSilent](ue_ue.SoundSourceBus.md#bautodeactivatewhensilent)
- [bBypassVolumeScaleForPriority](ue_ue.SoundSourceBus.md#bbypassvolumescaleforpriority)
- [bDebug](ue_ue.SoundSourceBus.md#bdebug)
- [bEnableAmplitudeEnvelopeAnalysis](ue_ue.SoundSourceBus.md#benableamplitudeenvelopeanalysis)
- [bEnableBakedFFTAnalysis](ue_ue.SoundSourceBus.md#benablebakedfftanalysis)
- [bHasConcatenatorNode](ue_ue.SoundSourceBus.md#bhasconcatenatornode)
- [bHasDelayNode](ue_ue.SoundSourceBus.md#bhasdelaynode)
- [bHasVirtualizeWhenSilent](ue_ue.SoundSourceBus.md#bhasvirtualizewhensilent)
- [bIsAmbisonics](ue_ue.SoundSourceBus.md#bisambisonics)
- [bLooping](ue_ue.SoundSourceBus.md#blooping)
- [bManualWordWrap](ue_ue.SoundSourceBus.md#bmanualwordwrap)
- [bMature](ue_ue.SoundSourceBus.md#bmature)
- [bOutputToBusOnly](ue_ue.SoundSourceBus.md#boutputtobusonly)
- [bOverrideConcurrency](ue_ue.SoundSourceBus.md#boverrideconcurrency)
- [bSeekableStreaming](ue_ue.SoundSourceBus.md#bseekablestreaming)
- [bSingleLine](ue_ue.SoundSourceBus.md#bsingleline)
- [bStreaming](ue_ue.SoundSourceBus.md#bstreaming)
- [bVirtualizeWhenSilent](ue_ue.SoundSourceBus.md#bvirtualizewhensilent)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundSourceBus.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundSourceBus.md#executeubergraph)
- [GetClass](ue_ue.SoundSourceBus.md#getclass)
- [GetName](ue_ue.SoundSourceBus.md#getname)
- [GetOuter](ue_ue.SoundSourceBus.md#getouter)
- [GetWorld](ue_ue.SoundSourceBus.md#getworld)
- [Find](ue_ue.SoundSourceBus.md#find)
- [Load](ue_ue.SoundSourceBus.md#load)
- [StaticClass](ue_ue.SoundSourceBus.md#staticclass)

## Constructors

### constructor

• **new SoundSourceBus**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundWave](ue_ue.SoundWave.md).[constructor](ue_ue.SoundWave.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[AssetImportData](ue_ue.SoundWave.md#assetimportdata)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[AttenuationSettings](ue_ue.SoundWave.md#attenuationsettings)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[BusSends](ue_ue.SoundWave.md#bussends)

___

### ChannelOffsets

• **ChannelOffsets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[ChannelOffsets](ue_ue.SoundWave.md#channeloffsets)

___

### ChannelSizes

• **ChannelSizes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[ChannelSizes](ue_ue.SoundWave.md#channelsizes)

___

### Comment

• **Comment**: `string`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[Comment](ue_ue.SoundWave.md#comment)

___

### CompressionQuality

• **CompressionQuality**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[CompressionQuality](ue_ue.SoundWave.md#compressionquality)

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[ConcurrencyOverrides](ue_ue.SoundWave.md#concurrencyoverrides)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[ConcurrencySet](ue_ue.SoundWave.md#concurrencyset)

___

### CookedEnvelopeTimeData

• **CookedEnvelopeTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveEnvelopeTimeData`](ue_ue.SoundWaveEnvelopeTimeData.md)\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[CookedEnvelopeTimeData](ue_ue.SoundWave.md#cookedenvelopetimedata)

___

### CookedSpectralTimeData

• **CookedSpectralTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveSpectralTimeData`](ue_ue.SoundWaveSpectralTimeData.md)\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[CookedSpectralTimeData](ue_ue.SoundWave.md#cookedspectraltimedata)

___

### Curves

• **Curves**: [`CurveTable`](ue_ue.CurveTable.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[Curves](ue_ue.SoundWave.md#curves)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[Duration](ue_ue.SoundWave.md#duration)

___

### EnvelopeFollowerAttackTime

• **EnvelopeFollowerAttackTime**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[EnvelopeFollowerAttackTime](ue_ue.SoundWave.md#envelopefollowerattacktime)

___

### EnvelopeFollowerFrameSize

• **EnvelopeFollowerFrameSize**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[EnvelopeFollowerFrameSize](ue_ue.SoundWave.md#envelopefollowerframesize)

___

### EnvelopeFollowerReleaseTime

• **EnvelopeFollowerReleaseTime**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[EnvelopeFollowerReleaseTime](ue_ue.SoundWave.md#envelopefollowerreleasetime)

___

### FFTAnalysisAttackTime

• **FFTAnalysisAttackTime**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[FFTAnalysisAttackTime](ue_ue.SoundWave.md#fftanalysisattacktime)

___

### FFTAnalysisFrameSize

• **FFTAnalysisFrameSize**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[FFTAnalysisFrameSize](ue_ue.SoundWave.md#fftanalysisframesize)

___

### FFTAnalysisReleaseTime

• **FFTAnalysisReleaseTime**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[FFTAnalysisReleaseTime](ue_ue.SoundWave.md#fftanalysisreleasetime)

___

### FFTSize

• **FFTSize**: [`ESoundWaveFFTSize`](../enums/ue_ue.ESoundWaveFFTSize.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[FFTSize](ue_ue.SoundWave.md#fftsize)

___

### FrequenciesToAnalyze

• **FrequenciesToAnalyze**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[FrequenciesToAnalyze](ue_ue.SoundWave.md#frequenciestoanalyze)

___

### InitialChunkSize

• **InitialChunkSize**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[InitialChunkSize](ue_ue.SoundWave.md#initialchunksize)

___

### InternalCurves

• **InternalCurves**: [`CurveTable`](ue_ue.CurveTable.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[InternalCurves](ue_ue.SoundWave.md#internalcurves)

___

### LoadingBehavior

• **LoadingBehavior**: [`ESoundWaveLoadingBehavior`](../enums/ue_ue.ESoundWaveLoadingBehavior.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[LoadingBehavior](ue_ue.SoundWave.md#loadingbehavior)

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[MaxConcurrentPlayCount](ue_ue.SoundWave.md#maxconcurrentplaycount)

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[MaxConcurrentResolutionRule](ue_ue.SoundWave.md#maxconcurrentresolutionrule)

___

### MaxDistance

• **MaxDistance**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[MaxDistance](ue_ue.SoundWave.md#maxdistance)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[Modulation](ue_ue.SoundWave.md#modulation)

___

### NumChannels

• **NumChannels**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[NumChannels](ue_ue.SoundWave.md#numchannels)

___

### OverrideSoundToUseForAnalysis

• **OverrideSoundToUseForAnalysis**: [`SoundWave`](ue_ue.SoundWave.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[OverrideSoundToUseForAnalysis](ue_ue.SoundWave.md#overridesoundtouseforanalysis)

___

### Pitch

• **Pitch**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[Pitch](ue_ue.SoundWave.md#pitch)

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[PreEffectBusSends](ue_ue.SoundWave.md#preeffectbussends)

___

### Priority

• **Priority**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[Priority](ue_ue.SoundWave.md#priority)

___

### SampleRate

• **SampleRate**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SampleRate](ue_ue.SoundWave.md#samplerate)

___

### SampleRateQuality

• **SampleRateQuality**: [`ESoundwaveSampleRateSettings`](../enums/ue_ue.ESoundwaveSampleRateSettings.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SampleRateQuality](ue_ue.SoundWave.md#sampleratequality)

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SoundClassObject](ue_ue.SoundWave.md#soundclassobject)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SoundConcurrencySettings](ue_ue.SoundWave.md#soundconcurrencysettings)

___

### SoundGroup

• **SoundGroup**: [`ESoundGroup`](../enums/ue_ue.ESoundGroup.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SoundGroup](ue_ue.SoundWave.md#soundgroup)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SoundSubmixObject](ue_ue.SoundWave.md#soundsubmixobject)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SoundSubmixSends](ue_ue.SoundWave.md#soundsubmixsends)

___

### SourceBusChannels

• **SourceBusChannels**: [`ESourceBusChannels`](../enums/ue_ue.ESourceBusChannels.md)

___

### SourceBusDuration

• **SourceBusDuration**: `number`

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SourceEffectChain](ue_ue.SoundWave.md#sourceeffectchain)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SourceFilePath](ue_ue.SoundWave.md#sourcefilepath)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SourceFileTimestamp](ue_ue.SoundWave.md#sourcefiletimestamp)

___

### SpokenText

• **SpokenText**: `string`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SpokenText](ue_ue.SoundWave.md#spokentext)

___

### StreamingPriority

• **StreamingPriority**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[StreamingPriority](ue_ue.SoundWave.md#streamingpriority)

___

### SubtitlePriority

• **SubtitlePriority**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[SubtitlePriority](ue_ue.SoundWave.md#subtitlepriority)

___

### Subtitles

• **Subtitles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubtitleCue`](ue_ue.SubtitleCue.md)\>

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[Subtitles](ue_ue.SoundWave.md#subtitles)

___

### TotalSamples

• **TotalSamples**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[TotalSamples](ue_ue.SoundWave.md#totalsamples)

___

### TreatFileAsLoopingForAnalysis

• **TreatFileAsLoopingForAnalysis**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[TreatFileAsLoopingForAnalysis](ue_ue.SoundWave.md#treatfileasloopingforanalysis)

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[VirtualizationMode](ue_ue.SoundWave.md#virtualizationmode)

___

### Volume

• **Volume**: `number`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[Volume](ue_ue.SoundWave.md#volume)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[__tid_Object__](ue_ue.SoundWave.md#__tid_object__)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[__tid_SoundBase__](ue_ue.SoundWave.md#__tid_soundbase__)

___

### \_\_tid\_SoundSourceBus\_\_

• **\_\_tid\_SoundSourceBus\_\_**: `boolean`

___

### \_\_tid\_SoundWave\_\_

• **\_\_tid\_SoundWave\_\_**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[__tid_SoundWave__](ue_ue.SoundWave.md#__tid_soundwave__)

___

### bAutoDeactivateWhenSilent

• **bAutoDeactivateWhenSilent**: `boolean`

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bBypassVolumeScaleForPriority](ue_ue.SoundWave.md#bbypassvolumescaleforpriority)

___

### bDebug

• **bDebug**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bDebug](ue_ue.SoundWave.md#bdebug)

___

### bEnableAmplitudeEnvelopeAnalysis

• **bEnableAmplitudeEnvelopeAnalysis**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bEnableAmplitudeEnvelopeAnalysis](ue_ue.SoundWave.md#benableamplitudeenvelopeanalysis)

___

### bEnableBakedFFTAnalysis

• **bEnableBakedFFTAnalysis**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bEnableBakedFFTAnalysis](ue_ue.SoundWave.md#benablebakedfftanalysis)

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bHasConcatenatorNode](ue_ue.SoundWave.md#bhasconcatenatornode)

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bHasDelayNode](ue_ue.SoundWave.md#bhasdelaynode)

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bHasVirtualizeWhenSilent](ue_ue.SoundWave.md#bhasvirtualizewhensilent)

___

### bIsAmbisonics

• **bIsAmbisonics**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bIsAmbisonics](ue_ue.SoundWave.md#bisambisonics)

___

### bLooping

• **bLooping**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bLooping](ue_ue.SoundWave.md#blooping)

___

### bManualWordWrap

• **bManualWordWrap**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bManualWordWrap](ue_ue.SoundWave.md#bmanualwordwrap)

___

### bMature

• **bMature**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bMature](ue_ue.SoundWave.md#bmature)

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bOutputToBusOnly](ue_ue.SoundWave.md#boutputtobusonly)

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bOverrideConcurrency](ue_ue.SoundWave.md#boverrideconcurrency)

___

### bSeekableStreaming

• **bSeekableStreaming**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bSeekableStreaming](ue_ue.SoundWave.md#bseekablestreaming)

___

### bSingleLine

• **bSingleLine**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bSingleLine](ue_ue.SoundWave.md#bsingleline)

___

### bStreaming

• **bStreaming**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bStreaming](ue_ue.SoundWave.md#bstreaming)

___

### bVirtualizeWhenSilent

• **bVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[bVirtualizeWhenSilent](ue_ue.SoundWave.md#bvirtualizewhensilent)

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

[SoundWave](ue_ue.SoundWave.md).[CreateDefaultSubobject](ue_ue.SoundWave.md#createdefaultsubobject)

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

[SoundWave](ue_ue.SoundWave.md).[ExecuteUbergraph](ue_ue.SoundWave.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[GetClass](ue_ue.SoundWave.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[GetName](ue_ue.SoundWave.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[GetOuter](ue_ue.SoundWave.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundWave](ue_ue.SoundWave.md).[GetWorld](ue_ue.SoundWave.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundSourceBus`](ue_ue.SoundSourceBus.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundSourceBus`](ue_ue.SoundSourceBus.md)

#### Overrides

[SoundWave](ue_ue.SoundWave.md).[Find](ue_ue.SoundWave.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundSourceBus`](ue_ue.SoundSourceBus.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundSourceBus`](ue_ue.SoundSourceBus.md)

#### Overrides

[SoundWave](ue_ue.SoundWave.md).[Load](ue_ue.SoundWave.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundWave](ue_ue.SoundWave.md).[StaticClass](ue_ue.SoundWave.md#staticclass)
