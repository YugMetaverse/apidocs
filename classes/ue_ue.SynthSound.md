[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SynthSound

# Class: SynthSound

[ue/ue](../modules/ue_ue.md).SynthSound

## Hierarchy

- [`SoundWaveProcedural`](ue_ue.SoundWaveProcedural.md)

  ↳ **`SynthSound`**

## Table of contents

### Constructors

- [constructor](ue_ue.SynthSound.md#constructor)

### Properties

- [AssetImportData](ue_ue.SynthSound.md#assetimportdata)
- [AttenuationSettings](ue_ue.SynthSound.md#attenuationsettings)
- [BusSends](ue_ue.SynthSound.md#bussends)
- [ChannelOffsets](ue_ue.SynthSound.md#channeloffsets)
- [ChannelSizes](ue_ue.SynthSound.md#channelsizes)
- [Comment](ue_ue.SynthSound.md#comment)
- [CompressionQuality](ue_ue.SynthSound.md#compressionquality)
- [ConcurrencyOverrides](ue_ue.SynthSound.md#concurrencyoverrides)
- [ConcurrencySet](ue_ue.SynthSound.md#concurrencyset)
- [CookedEnvelopeTimeData](ue_ue.SynthSound.md#cookedenvelopetimedata)
- [CookedSpectralTimeData](ue_ue.SynthSound.md#cookedspectraltimedata)
- [Curves](ue_ue.SynthSound.md#curves)
- [Duration](ue_ue.SynthSound.md#duration)
- [EnvelopeFollowerAttackTime](ue_ue.SynthSound.md#envelopefollowerattacktime)
- [EnvelopeFollowerFrameSize](ue_ue.SynthSound.md#envelopefollowerframesize)
- [EnvelopeFollowerReleaseTime](ue_ue.SynthSound.md#envelopefollowerreleasetime)
- [FFTAnalysisAttackTime](ue_ue.SynthSound.md#fftanalysisattacktime)
- [FFTAnalysisFrameSize](ue_ue.SynthSound.md#fftanalysisframesize)
- [FFTAnalysisReleaseTime](ue_ue.SynthSound.md#fftanalysisreleasetime)
- [FFTSize](ue_ue.SynthSound.md#fftsize)
- [FrequenciesToAnalyze](ue_ue.SynthSound.md#frequenciestoanalyze)
- [InitialChunkSize](ue_ue.SynthSound.md#initialchunksize)
- [InternalCurves](ue_ue.SynthSound.md#internalcurves)
- [LoadingBehavior](ue_ue.SynthSound.md#loadingbehavior)
- [MaxConcurrentPlayCount](ue_ue.SynthSound.md#maxconcurrentplaycount)
- [MaxConcurrentResolutionRule](ue_ue.SynthSound.md#maxconcurrentresolutionrule)
- [MaxDistance](ue_ue.SynthSound.md#maxdistance)
- [Modulation](ue_ue.SynthSound.md#modulation)
- [NumChannels](ue_ue.SynthSound.md#numchannels)
- [OverrideSoundToUseForAnalysis](ue_ue.SynthSound.md#overridesoundtouseforanalysis)
- [OwningSynthComponent](ue_ue.SynthSound.md#owningsynthcomponent)
- [Pitch](ue_ue.SynthSound.md#pitch)
- [PreEffectBusSends](ue_ue.SynthSound.md#preeffectbussends)
- [Priority](ue_ue.SynthSound.md#priority)
- [SampleRate](ue_ue.SynthSound.md#samplerate)
- [SampleRateQuality](ue_ue.SynthSound.md#sampleratequality)
- [SoundClassObject](ue_ue.SynthSound.md#soundclassobject)
- [SoundConcurrencySettings](ue_ue.SynthSound.md#soundconcurrencysettings)
- [SoundGroup](ue_ue.SynthSound.md#soundgroup)
- [SoundSubmixObject](ue_ue.SynthSound.md#soundsubmixobject)
- [SoundSubmixSends](ue_ue.SynthSound.md#soundsubmixsends)
- [SourceEffectChain](ue_ue.SynthSound.md#sourceeffectchain)
- [SourceFilePath](ue_ue.SynthSound.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.SynthSound.md#sourcefiletimestamp)
- [SpokenText](ue_ue.SynthSound.md#spokentext)
- [StreamingPriority](ue_ue.SynthSound.md#streamingpriority)
- [SubtitlePriority](ue_ue.SynthSound.md#subtitlepriority)
- [Subtitles](ue_ue.SynthSound.md#subtitles)
- [TotalSamples](ue_ue.SynthSound.md#totalsamples)
- [TreatFileAsLoopingForAnalysis](ue_ue.SynthSound.md#treatfileasloopingforanalysis)
- [VirtualizationMode](ue_ue.SynthSound.md#virtualizationmode)
- [Volume](ue_ue.SynthSound.md#volume)
- [\_\_tid\_Object\_\_](ue_ue.SynthSound.md#__tid_object__)
- [\_\_tid\_SoundBase\_\_](ue_ue.SynthSound.md#__tid_soundbase__)
- [\_\_tid\_SoundWaveProcedural\_\_](ue_ue.SynthSound.md#__tid_soundwaveprocedural__)
- [\_\_tid\_SoundWave\_\_](ue_ue.SynthSound.md#__tid_soundwave__)
- [\_\_tid\_SynthSound\_\_](ue_ue.SynthSound.md#__tid_synthsound__)
- [bBypassVolumeScaleForPriority](ue_ue.SynthSound.md#bbypassvolumescaleforpriority)
- [bDebug](ue_ue.SynthSound.md#bdebug)
- [bEnableAmplitudeEnvelopeAnalysis](ue_ue.SynthSound.md#benableamplitudeenvelopeanalysis)
- [bEnableBakedFFTAnalysis](ue_ue.SynthSound.md#benablebakedfftanalysis)
- [bHasConcatenatorNode](ue_ue.SynthSound.md#bhasconcatenatornode)
- [bHasDelayNode](ue_ue.SynthSound.md#bhasdelaynode)
- [bHasVirtualizeWhenSilent](ue_ue.SynthSound.md#bhasvirtualizewhensilent)
- [bIsAmbisonics](ue_ue.SynthSound.md#bisambisonics)
- [bLooping](ue_ue.SynthSound.md#blooping)
- [bManualWordWrap](ue_ue.SynthSound.md#bmanualwordwrap)
- [bMature](ue_ue.SynthSound.md#bmature)
- [bOutputToBusOnly](ue_ue.SynthSound.md#boutputtobusonly)
- [bOverrideConcurrency](ue_ue.SynthSound.md#boverrideconcurrency)
- [bSeekableStreaming](ue_ue.SynthSound.md#bseekablestreaming)
- [bSingleLine](ue_ue.SynthSound.md#bsingleline)
- [bStreaming](ue_ue.SynthSound.md#bstreaming)
- [bVirtualizeWhenSilent](ue_ue.SynthSound.md#bvirtualizewhensilent)

### Methods

- [CreateDefaultSubobject](ue_ue.SynthSound.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SynthSound.md#executeubergraph)
- [GetClass](ue_ue.SynthSound.md#getclass)
- [GetName](ue_ue.SynthSound.md#getname)
- [GetOuter](ue_ue.SynthSound.md#getouter)
- [GetWorld](ue_ue.SynthSound.md#getworld)
- [Find](ue_ue.SynthSound.md#find)
- [Load](ue_ue.SynthSound.md#load)
- [StaticClass](ue_ue.SynthSound.md#staticclass)

## Constructors

### constructor

• **new SynthSound**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[constructor](ue_ue.SoundWaveProcedural.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[AssetImportData](ue_ue.SoundWaveProcedural.md#assetimportdata)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[AttenuationSettings](ue_ue.SoundWaveProcedural.md#attenuationsettings)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[BusSends](ue_ue.SoundWaveProcedural.md#bussends)

___

### ChannelOffsets

• **ChannelOffsets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ChannelOffsets](ue_ue.SoundWaveProcedural.md#channeloffsets)

___

### ChannelSizes

• **ChannelSizes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ChannelSizes](ue_ue.SoundWaveProcedural.md#channelsizes)

___

### Comment

• **Comment**: `string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Comment](ue_ue.SoundWaveProcedural.md#comment)

___

### CompressionQuality

• **CompressionQuality**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[CompressionQuality](ue_ue.SoundWaveProcedural.md#compressionquality)

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ConcurrencyOverrides](ue_ue.SoundWaveProcedural.md#concurrencyoverrides)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ConcurrencySet](ue_ue.SoundWaveProcedural.md#concurrencyset)

___

### CookedEnvelopeTimeData

• **CookedEnvelopeTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveEnvelopeTimeData`](ue_ue.SoundWaveEnvelopeTimeData.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[CookedEnvelopeTimeData](ue_ue.SoundWaveProcedural.md#cookedenvelopetimedata)

___

### CookedSpectralTimeData

• **CookedSpectralTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveSpectralTimeData`](ue_ue.SoundWaveSpectralTimeData.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[CookedSpectralTimeData](ue_ue.SoundWaveProcedural.md#cookedspectraltimedata)

___

### Curves

• **Curves**: [`CurveTable`](ue_ue.CurveTable.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Curves](ue_ue.SoundWaveProcedural.md#curves)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Duration](ue_ue.SoundWaveProcedural.md#duration)

___

### EnvelopeFollowerAttackTime

• **EnvelopeFollowerAttackTime**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[EnvelopeFollowerAttackTime](ue_ue.SoundWaveProcedural.md#envelopefollowerattacktime)

___

### EnvelopeFollowerFrameSize

• **EnvelopeFollowerFrameSize**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[EnvelopeFollowerFrameSize](ue_ue.SoundWaveProcedural.md#envelopefollowerframesize)

___

### EnvelopeFollowerReleaseTime

• **EnvelopeFollowerReleaseTime**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[EnvelopeFollowerReleaseTime](ue_ue.SoundWaveProcedural.md#envelopefollowerreleasetime)

___

### FFTAnalysisAttackTime

• **FFTAnalysisAttackTime**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FFTAnalysisAttackTime](ue_ue.SoundWaveProcedural.md#fftanalysisattacktime)

___

### FFTAnalysisFrameSize

• **FFTAnalysisFrameSize**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FFTAnalysisFrameSize](ue_ue.SoundWaveProcedural.md#fftanalysisframesize)

___

### FFTAnalysisReleaseTime

• **FFTAnalysisReleaseTime**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FFTAnalysisReleaseTime](ue_ue.SoundWaveProcedural.md#fftanalysisreleasetime)

___

### FFTSize

• **FFTSize**: [`ESoundWaveFFTSize`](../enums/ue_ue.ESoundWaveFFTSize.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FFTSize](ue_ue.SoundWaveProcedural.md#fftsize)

___

### FrequenciesToAnalyze

• **FrequenciesToAnalyze**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FrequenciesToAnalyze](ue_ue.SoundWaveProcedural.md#frequenciestoanalyze)

___

### InitialChunkSize

• **InitialChunkSize**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[InitialChunkSize](ue_ue.SoundWaveProcedural.md#initialchunksize)

___

### InternalCurves

• **InternalCurves**: [`CurveTable`](ue_ue.CurveTable.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[InternalCurves](ue_ue.SoundWaveProcedural.md#internalcurves)

___

### LoadingBehavior

• **LoadingBehavior**: [`ESoundWaveLoadingBehavior`](../enums/ue_ue.ESoundWaveLoadingBehavior.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[LoadingBehavior](ue_ue.SoundWaveProcedural.md#loadingbehavior)

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[MaxConcurrentPlayCount](ue_ue.SoundWaveProcedural.md#maxconcurrentplaycount)

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[MaxConcurrentResolutionRule](ue_ue.SoundWaveProcedural.md#maxconcurrentresolutionrule)

___

### MaxDistance

• **MaxDistance**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[MaxDistance](ue_ue.SoundWaveProcedural.md#maxdistance)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Modulation](ue_ue.SoundWaveProcedural.md#modulation)

___

### NumChannels

• **NumChannels**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[NumChannels](ue_ue.SoundWaveProcedural.md#numchannels)

___

### OverrideSoundToUseForAnalysis

• **OverrideSoundToUseForAnalysis**: [`SoundWave`](ue_ue.SoundWave.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[OverrideSoundToUseForAnalysis](ue_ue.SoundWaveProcedural.md#overridesoundtouseforanalysis)

___

### OwningSynthComponent

• **OwningSynthComponent**: [`SynthComponent`](ue_ue.SynthComponent.md)

___

### Pitch

• **Pitch**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Pitch](ue_ue.SoundWaveProcedural.md#pitch)

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[PreEffectBusSends](ue_ue.SoundWaveProcedural.md#preeffectbussends)

___

### Priority

• **Priority**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Priority](ue_ue.SoundWaveProcedural.md#priority)

___

### SampleRate

• **SampleRate**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SampleRate](ue_ue.SoundWaveProcedural.md#samplerate)

___

### SampleRateQuality

• **SampleRateQuality**: [`ESoundwaveSampleRateSettings`](../enums/ue_ue.ESoundwaveSampleRateSettings.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SampleRateQuality](ue_ue.SoundWaveProcedural.md#sampleratequality)

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundClassObject](ue_ue.SoundWaveProcedural.md#soundclassobject)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundConcurrencySettings](ue_ue.SoundWaveProcedural.md#soundconcurrencysettings)

___

### SoundGroup

• **SoundGroup**: [`ESoundGroup`](../enums/ue_ue.ESoundGroup.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundGroup](ue_ue.SoundWaveProcedural.md#soundgroup)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundSubmixObject](ue_ue.SoundWaveProcedural.md#soundsubmixobject)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundSubmixSends](ue_ue.SoundWaveProcedural.md#soundsubmixsends)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SourceEffectChain](ue_ue.SoundWaveProcedural.md#sourceeffectchain)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SourceFilePath](ue_ue.SoundWaveProcedural.md#sourcefilepath)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SourceFileTimestamp](ue_ue.SoundWaveProcedural.md#sourcefiletimestamp)

___

### SpokenText

• **SpokenText**: `string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SpokenText](ue_ue.SoundWaveProcedural.md#spokentext)

___

### StreamingPriority

• **StreamingPriority**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[StreamingPriority](ue_ue.SoundWaveProcedural.md#streamingpriority)

___

### SubtitlePriority

• **SubtitlePriority**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SubtitlePriority](ue_ue.SoundWaveProcedural.md#subtitlepriority)

___

### Subtitles

• **Subtitles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubtitleCue`](ue_ue.SubtitleCue.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Subtitles](ue_ue.SoundWaveProcedural.md#subtitles)

___

### TotalSamples

• **TotalSamples**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[TotalSamples](ue_ue.SoundWaveProcedural.md#totalsamples)

___

### TreatFileAsLoopingForAnalysis

• **TreatFileAsLoopingForAnalysis**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[TreatFileAsLoopingForAnalysis](ue_ue.SoundWaveProcedural.md#treatfileasloopingforanalysis)

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[VirtualizationMode](ue_ue.SoundWaveProcedural.md#virtualizationmode)

___

### Volume

• **Volume**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Volume](ue_ue.SoundWaveProcedural.md#volume)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[__tid_Object__](ue_ue.SoundWaveProcedural.md#__tid_object__)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[__tid_SoundBase__](ue_ue.SoundWaveProcedural.md#__tid_soundbase__)

___

### \_\_tid\_SoundWaveProcedural\_\_

• **\_\_tid\_SoundWaveProcedural\_\_**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[__tid_SoundWaveProcedural__](ue_ue.SoundWaveProcedural.md#__tid_soundwaveprocedural__)

___

### \_\_tid\_SoundWave\_\_

• **\_\_tid\_SoundWave\_\_**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[__tid_SoundWave__](ue_ue.SoundWaveProcedural.md#__tid_soundwave__)

___

### \_\_tid\_SynthSound\_\_

• **\_\_tid\_SynthSound\_\_**: `boolean`

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bBypassVolumeScaleForPriority](ue_ue.SoundWaveProcedural.md#bbypassvolumescaleforpriority)

___

### bDebug

• **bDebug**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bDebug](ue_ue.SoundWaveProcedural.md#bdebug)

___

### bEnableAmplitudeEnvelopeAnalysis

• **bEnableAmplitudeEnvelopeAnalysis**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bEnableAmplitudeEnvelopeAnalysis](ue_ue.SoundWaveProcedural.md#benableamplitudeenvelopeanalysis)

___

### bEnableBakedFFTAnalysis

• **bEnableBakedFFTAnalysis**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bEnableBakedFFTAnalysis](ue_ue.SoundWaveProcedural.md#benablebakedfftanalysis)

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bHasConcatenatorNode](ue_ue.SoundWaveProcedural.md#bhasconcatenatornode)

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bHasDelayNode](ue_ue.SoundWaveProcedural.md#bhasdelaynode)

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bHasVirtualizeWhenSilent](ue_ue.SoundWaveProcedural.md#bhasvirtualizewhensilent)

___

### bIsAmbisonics

• **bIsAmbisonics**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bIsAmbisonics](ue_ue.SoundWaveProcedural.md#bisambisonics)

___

### bLooping

• **bLooping**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bLooping](ue_ue.SoundWaveProcedural.md#blooping)

___

### bManualWordWrap

• **bManualWordWrap**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bManualWordWrap](ue_ue.SoundWaveProcedural.md#bmanualwordwrap)

___

### bMature

• **bMature**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bMature](ue_ue.SoundWaveProcedural.md#bmature)

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bOutputToBusOnly](ue_ue.SoundWaveProcedural.md#boutputtobusonly)

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bOverrideConcurrency](ue_ue.SoundWaveProcedural.md#boverrideconcurrency)

___

### bSeekableStreaming

• **bSeekableStreaming**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bSeekableStreaming](ue_ue.SoundWaveProcedural.md#bseekablestreaming)

___

### bSingleLine

• **bSingleLine**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bSingleLine](ue_ue.SoundWaveProcedural.md#bsingleline)

___

### bStreaming

• **bStreaming**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bStreaming](ue_ue.SoundWaveProcedural.md#bstreaming)

___

### bVirtualizeWhenSilent

• **bVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bVirtualizeWhenSilent](ue_ue.SoundWaveProcedural.md#bvirtualizewhensilent)

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

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[CreateDefaultSubobject](ue_ue.SoundWaveProcedural.md#createdefaultsubobject)

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

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ExecuteUbergraph](ue_ue.SoundWaveProcedural.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[GetClass](ue_ue.SoundWaveProcedural.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[GetName](ue_ue.SoundWaveProcedural.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[GetOuter](ue_ue.SoundWaveProcedural.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[GetWorld](ue_ue.SoundWaveProcedural.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SynthSound`](ue_ue.SynthSound.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SynthSound`](ue_ue.SynthSound.md)

#### Overrides

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Find](ue_ue.SoundWaveProcedural.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SynthSound`](ue_ue.SynthSound.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SynthSound`](ue_ue.SynthSound.md)

#### Overrides

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Load](ue_ue.SoundWaveProcedural.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[StaticClass](ue_ue.SoundWaveProcedural.md#staticclass)
